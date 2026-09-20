<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee4dfac4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ee4dfac4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:place-of-worship" {...props}></Icon>
