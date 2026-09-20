<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsay_9bjz.css';
import '../../css/e/e56ncghit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xsay_9bjz"/><path class="e56ncghit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-pull-request-locked-16" {...props}></Icon>
