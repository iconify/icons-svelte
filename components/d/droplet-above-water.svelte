<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkzximbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qkzximbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-above-water" {...props}></Icon>
