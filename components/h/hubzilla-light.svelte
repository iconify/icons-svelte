<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv8hv5_7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bv8hv5_7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hubzilla-light" {...props}></Icon>
