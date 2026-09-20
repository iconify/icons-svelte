<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw0s58bcd.css';
import '../../css/i/imnugdlgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bw0s58bcd"/><path class="imnugdlgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:down-left-arrow" {...props}></Icon>
