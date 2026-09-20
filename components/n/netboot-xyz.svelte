<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu922hb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gu922hb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netboot-xyz" {...props}></Icon>
