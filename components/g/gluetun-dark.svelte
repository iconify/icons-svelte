<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh54a7btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sh54a7btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gluetun-dark" {...props}></Icon>
