<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc2gsxl_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc2gsxl_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:activitypub" {...props}></Icon>
