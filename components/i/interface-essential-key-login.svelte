<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6twclbpr.css';
import '../../css/p/poe7slbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u6twclbpr"/><path class="poe7slbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-key-login" {...props}></Icon>
