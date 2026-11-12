<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3ac8-n2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3ac8-n2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fedex-light" {...props}></Icon>
