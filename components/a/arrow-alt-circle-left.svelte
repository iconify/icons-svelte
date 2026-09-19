<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcbitzb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcbitzb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-alt-circle-left" {...props}></Icon>
