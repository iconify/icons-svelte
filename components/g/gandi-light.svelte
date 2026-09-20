<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozgm-tbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ozgm-tbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gandi-light" {...props}></Icon>
