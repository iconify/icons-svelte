<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng3z04b6k.css';
import '../../css/l/l2gxg7bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ng3z04b6k"/><path class="l2gxg7bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-time" {...props}></Icon>
