<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spcaiwx2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spcaiwx2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:help" {...props}></Icon>
