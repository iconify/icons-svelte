<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7lf_dbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w7lf_dbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hetrixtools" {...props}></Icon>
