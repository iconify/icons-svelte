<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2_vu7bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q2_vu7bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:controls-vertical" {...props}></Icon>
