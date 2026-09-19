<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nte0_mbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nte0_mbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:arrow-circle-up-sparkle" {...props}></Icon>
