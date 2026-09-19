<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni-6x9bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ni-6x9bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:cloud" {...props}></Icon>
