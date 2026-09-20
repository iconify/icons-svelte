<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4_wkcoza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="w4_wkcoza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:jewelry-store-11" {...props}></Icon>
