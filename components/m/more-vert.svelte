<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ema3rwbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ema3rwbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:more-vert" {...props}></Icon>
