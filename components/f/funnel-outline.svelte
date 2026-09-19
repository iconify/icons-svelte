<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnjxj5bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bnjxj5bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:funnel-outline" {...props}></Icon>
