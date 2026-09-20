<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk3vthbjv.css';
import '../../css/e/ewd4-9b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nk3vthbjv"/><circle class="ewd4-9b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:camera" {...props}></Icon>
