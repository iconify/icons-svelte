<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inlhb1gzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="inlhb1gzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-to-top" {...props}></Icon>
