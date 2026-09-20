<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nudrhyb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="nudrhyb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ecg-waves" {...props}></Icon>
