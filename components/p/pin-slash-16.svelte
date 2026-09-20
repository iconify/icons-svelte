<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drhwmzukw.css';
import '../../css/n/noii36_6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="drhwmzukw"/><path class="noii36_6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pin-slash-16" {...props}></Icon>
