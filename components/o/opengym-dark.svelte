<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf994ezlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pf994ezlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opengym-dark" {...props}></Icon>
