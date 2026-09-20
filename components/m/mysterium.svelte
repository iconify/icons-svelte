<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dne2_ig2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dne2_ig2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mysterium" {...props}></Icon>
