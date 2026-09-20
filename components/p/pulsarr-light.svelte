<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfifdy1xw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yfifdy1xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pulsarr-light" {...props}></Icon>
