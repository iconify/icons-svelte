<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go4x3ob7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="go4x3ob7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:asrock-dark" {...props}></Icon>
