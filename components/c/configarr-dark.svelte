<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip70a665c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ip70a665c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:configarr-dark" {...props}></Icon>
