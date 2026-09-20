<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygxly9bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygxly9bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dji-logbook-dark" {...props}></Icon>
