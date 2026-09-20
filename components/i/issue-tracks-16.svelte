<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk5hyp-iw.css';
import '../../css/u/ua94ilb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mk5hyp-iw"/><path class="ua94ilb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-tracks-16" {...props}></Icon>
