<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxxivlghf.css';
import '../../css/s/s4f0-m1sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yxxivlghf"/><path class="s4f0-m1sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:continuwuity-dark" {...props}></Icon>
