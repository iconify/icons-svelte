<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lil__im4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lil__im4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:circular-graph" {...props}></Icon>
