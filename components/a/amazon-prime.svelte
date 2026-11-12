<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjaq-1bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mjaq-1bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-prime" {...props}></Icon>
