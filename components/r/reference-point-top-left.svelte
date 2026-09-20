<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv731-ofg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bv731-ofg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:reference-point-top-left" {...props}></Icon>
