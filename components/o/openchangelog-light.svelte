<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux25dn--w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ux25dn--w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openchangelog-light" {...props}></Icon>
