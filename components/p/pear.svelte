<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jejrh1gth.css';
import '../../css/v/vym5f4c_s.css';
import '../../css/o/optgq2b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jejrh1gth"/><path class="vym5f4c_s"/><path class="optgq2b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pear" {...props}></Icon>
