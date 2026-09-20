<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx_g5rccz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nx_g5rccz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:equal" {...props}></Icon>
