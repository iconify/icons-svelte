<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfui54jbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hfui54jbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:avianex" {...props}></Icon>
