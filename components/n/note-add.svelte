<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_856-4mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_856-4mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:note-add" {...props}></Icon>
