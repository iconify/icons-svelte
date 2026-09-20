<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfrim3bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nfrim3bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-down-two-outline" {...props}></Icon>
