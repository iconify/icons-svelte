<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drbsluqal.css';
import '../../css/q/q5hhuwpif.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="drbsluqal"/><path class="q5hhuwpif"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-check-20-bold" {...props}></Icon>
