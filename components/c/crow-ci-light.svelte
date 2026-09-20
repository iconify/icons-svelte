<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i73vyxe7x.css';
import '../../css/n/nbm911b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i73vyxe7x"/><path class="nbm911b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crow-ci-light" {...props}></Icon>
