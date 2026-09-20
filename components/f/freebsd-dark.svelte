<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggw6gxb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ggw6gxb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freebsd-dark" {...props}></Icon>
