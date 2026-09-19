<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnvxsh6ed.css';
import '../../css/w/wp_6hx3_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lnvxsh6ed"/><path class="wp_6hx3_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cloud-offline-outline" {...props}></Icon>
