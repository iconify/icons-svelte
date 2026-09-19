<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daqra0bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="daqra0bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-graph-up-left" {...props}></Icon>
