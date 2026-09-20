<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz2n7j-_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fz2n7j-_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fider-light" {...props}></Icon>
