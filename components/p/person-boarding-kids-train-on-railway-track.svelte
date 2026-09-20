<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8udhfbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w8udhfbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-boarding-kids-train-on-railway-track" {...props}></Icon>
