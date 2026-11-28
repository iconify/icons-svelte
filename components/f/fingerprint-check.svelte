<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icy7k2bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icy7k2bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fingerprint-check" {...props}></Icon>
