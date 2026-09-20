<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6slewbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z6slewbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:certimate-dark" {...props}></Icon>
