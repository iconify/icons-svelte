<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha2ibjb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ha2ibjb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-above-outstretched-hand" {...props}></Icon>
