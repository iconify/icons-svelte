<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs-88kber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hs-88kber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aiometadata" {...props}></Icon>
