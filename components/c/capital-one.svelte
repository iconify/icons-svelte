<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0yul3-vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f0yul3-vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:capital-one" {...props}></Icon>
