<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgl83sa6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rgl83sa6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:fingerprint-outline" {...props}></Icon>
