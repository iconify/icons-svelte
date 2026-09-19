<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjvc_dj1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjvc_dj1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:paw" {...props}></Icon>
