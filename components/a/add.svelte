<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5zn8ca3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q5zn8ca3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:add" {...props}></Icon>
