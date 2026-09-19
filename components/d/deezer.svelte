<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4w89svje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="d4w89svje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:deezer" {...props}></Icon>
