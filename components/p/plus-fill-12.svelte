<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhbw-h_zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rhbw-h_zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plus-fill-12" {...props}></Icon>
