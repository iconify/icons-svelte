<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_byvbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3_byvbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opnsense" {...props}></Icon>
