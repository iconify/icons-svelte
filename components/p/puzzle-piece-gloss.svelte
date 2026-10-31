<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yghrc8bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yghrc8bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:puzzle-piece-gloss" {...props}></Icon>
