<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol7k2zbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ol7k2zbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feedbin-dark" {...props}></Icon>
