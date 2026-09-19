<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8zw34-dy.css';
import '../../css/d/d84_2zbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g8zw34-dy"/><path class="d84_2zbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-npm" {...props}></Icon>
