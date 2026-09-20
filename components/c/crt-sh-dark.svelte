<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcihm-0sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xcihm-0sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crt-sh-dark" {...props}></Icon>
