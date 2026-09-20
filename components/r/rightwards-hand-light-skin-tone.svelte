<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nalzdz3gx.css';
import '../../css/n/nw_fw7zya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="nalzdz3gx"/><path class="nw_fw7zya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:rightwards-hand-light-skin-tone" {...props}></Icon>
