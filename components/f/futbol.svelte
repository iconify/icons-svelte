<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8-diacjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f8-diacjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:futbol" {...props}></Icon>
