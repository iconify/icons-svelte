<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf0cu3pan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kf0cu3pan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chevereto" {...props}></Icon>
