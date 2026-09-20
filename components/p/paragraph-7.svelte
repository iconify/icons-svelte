<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgg9tabhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dgg9tabhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:paragraph-7" {...props}></Icon>
