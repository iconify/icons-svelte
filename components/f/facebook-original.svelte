<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wayg92b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="wayg92b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:facebook-original" {...props}></Icon>
