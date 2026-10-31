<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd89ibzna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kd89ibzna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-gabled-building" {...props}></Icon>
