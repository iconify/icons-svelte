<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2627vwdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y2627vwdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:automad-dark" {...props}></Icon>
