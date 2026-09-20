<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k74075dxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k74075dxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:discussion-closed-16" {...props}></Icon>
