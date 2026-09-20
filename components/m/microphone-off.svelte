<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns20xvbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ns20xvbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:microphone-off" {...props}></Icon>
