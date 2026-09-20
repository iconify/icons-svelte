<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfj-wcb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cfj-wcb0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:microphone-off-solid" {...props}></Icon>
