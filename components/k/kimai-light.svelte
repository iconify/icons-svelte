<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl0z4qqxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sl0z4qqxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kimai-light" {...props}></Icon>
