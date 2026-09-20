<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml2iv7saz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ml2iv7saz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agam-space-dark" {...props}></Icon>
