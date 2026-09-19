<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npbkbobuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npbkbobuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:pool" {...props}></Icon>
