<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewi3usmnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ewi3usmnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-above-outstretched-hand" {...props}></Icon>
