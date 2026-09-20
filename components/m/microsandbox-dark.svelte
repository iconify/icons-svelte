<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm_mfnb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dm_mfnb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsandbox-dark" {...props}></Icon>
