<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_jj5jfvq.css';
import '../../css/l/lrth8l6xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f_jj5jfvq"/><path class="lrth8l6xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-hypper" {...props}></Icon>
