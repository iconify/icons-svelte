<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgbsu93mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rgbsu93mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:europris-dark" {...props}></Icon>
