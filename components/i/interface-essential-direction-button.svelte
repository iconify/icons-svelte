<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz8e6mgxq.css';
import '../../css/v/vj-egbxkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iz8e6mgxq"/><path class="vj-egbxkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-direction-button" {...props}></Icon>
