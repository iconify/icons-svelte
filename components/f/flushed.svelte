<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awf1i5bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="awf1i5bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:flushed" {...props}></Icon>
