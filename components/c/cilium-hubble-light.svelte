<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy7zh6btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dy7zh6btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cilium-hubble-light" {...props}></Icon>
