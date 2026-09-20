<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp4zgl_dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dp4zgl_dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inexogy-dark" {...props}></Icon>
