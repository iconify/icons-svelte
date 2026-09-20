<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q03w996mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q03w996mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:keyboard-line" {...props}></Icon>
