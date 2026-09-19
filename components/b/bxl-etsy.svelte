<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_jre5onb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_jre5onb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-etsy" {...props}></Icon>
