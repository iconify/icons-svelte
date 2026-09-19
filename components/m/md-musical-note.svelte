<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0yp0ryff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0yp0ryff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-musical-note" {...props}></Icon>
