<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdom31c5r.css';
import '../../css/w/wp43u2bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fdom31c5r"/><path class="wp43u2bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:harddrive" {...props}></Icon>
