<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uehppmv_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uehppmv_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homematic-ip-dark" {...props}></Icon>
