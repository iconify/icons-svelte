<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcg2pob3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mcg2pob3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:healthchecks-light" {...props}></Icon>
