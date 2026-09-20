<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfhzjy5gb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfhzjy5gb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-kanban-solid" {...props}></Icon>
