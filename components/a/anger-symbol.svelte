<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz4b90hlv.css';
import '../../css/h/hltafxbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="oz4b90hlv"/><path class="hltafxbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:anger-symbol" {...props}></Icon>
