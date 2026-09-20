<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd0x4bpta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pd0x4bpta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:moon" {...props}></Icon>
