<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5eqilbmm.css';
import '../../css/s/s5h2abbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5eqilbmm"/><path class="s5h2abbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-3-line" {...props}></Icon>
