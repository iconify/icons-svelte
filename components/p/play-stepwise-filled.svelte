<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvfgo8b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cvfgo8b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:play-stepwise-filled" {...props}></Icon>
