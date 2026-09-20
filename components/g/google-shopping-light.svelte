<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whv-2bcvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="whv-2bcvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-shopping-light" {...props}></Icon>
