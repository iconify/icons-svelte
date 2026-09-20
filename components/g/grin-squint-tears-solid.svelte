<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0v2cdcqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z0v2cdcqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:grin-squint-tears-solid" {...props}></Icon>
