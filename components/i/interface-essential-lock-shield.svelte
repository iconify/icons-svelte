<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgcl_acrx.css';
import '../../css/n/n83ma-b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jgcl_acrx"/><path class="n83ma-b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-lock-shield" {...props}></Icon>
