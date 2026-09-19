<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtp_siu6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mtp_siu6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:download-stroke-16" {...props}></Icon>
