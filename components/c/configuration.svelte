<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0ksu7uqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0ksu7uqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:configuration" {...props}></Icon>
