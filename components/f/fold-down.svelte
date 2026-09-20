<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvn6i9e6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="wvn6i9e6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:fold-down" {...props}></Icon>
