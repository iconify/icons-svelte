<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvg2-sbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mvg2-sbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:almalinux-light" {...props}></Icon>
