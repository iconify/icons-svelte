<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqefk9bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mqefk9bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkbox" {...props}></Icon>
