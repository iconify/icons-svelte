<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz7s1z9sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wz7s1z9sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:cursor" {...props}></Icon>
