<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpxcr_mnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hpxcr_mnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:flower" {...props}></Icon>
