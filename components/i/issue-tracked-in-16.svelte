<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk5hyp-iw.css';
import '../../css/d/dhnqkbc9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mk5hyp-iw"/><path class="dhnqkbc9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-tracked-in-16" {...props}></Icon>
