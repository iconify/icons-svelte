<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkbfyf_pr.css';
import '../../css/m/md69zlb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jkbfyf_pr"/><path class="md69zlb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:location" {...props}></Icon>
