<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq75i1y9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vq75i1y9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-female" {...props}></Icon>
