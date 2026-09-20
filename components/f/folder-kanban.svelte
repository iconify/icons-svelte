<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wczeb9phz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wczeb9phz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:folder-kanban" {...props}></Icon>
