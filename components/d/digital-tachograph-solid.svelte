<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l16sp9c4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l16sp9c4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:digital-tachograph-solid" {...props}></Icon>
