<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsbsitslb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="lsbsitslb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-compare" {...props}></Icon>
