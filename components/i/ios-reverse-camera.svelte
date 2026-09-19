<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0hbmqx4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k0hbmqx4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-reverse-camera" {...props}></Icon>
