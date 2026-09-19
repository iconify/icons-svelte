<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f11fmib_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f11fmib_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cube" {...props}></Icon>
