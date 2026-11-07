<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2n33z6pt.css';
import '../../css/d/dr_uzfb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f2n33z6pt"/><path class="dr_uzfb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plmail-light" {...props}></Icon>
