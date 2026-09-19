<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5yf1eshv.css';
import '../../css/t/toc-9jzis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5yf1eshv"/><path class="toc-9jzis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cloud-light-rain" {...props}></Icon>
