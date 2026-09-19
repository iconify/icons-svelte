<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl2ih_b2x.css';
import '../../css/q/qrgcibvkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl2ih_b2x"/><path class="qrgcibvkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-digitalocean" {...props}></Icon>
