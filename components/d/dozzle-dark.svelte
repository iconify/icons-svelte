<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxg8a_oyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bxg8a_oyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dozzle-dark" {...props}></Icon>
