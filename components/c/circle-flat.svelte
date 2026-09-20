<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9d05fmzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="y9d05fmzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:circle-flat" {...props}></Icon>
