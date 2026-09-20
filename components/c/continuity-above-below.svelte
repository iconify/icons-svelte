<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icmri56gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="icmri56gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:continuity-above-below" {...props}></Icon>
