<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge0zdlm-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ge0zdlm-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:health-microscope" {...props}></Icon>
