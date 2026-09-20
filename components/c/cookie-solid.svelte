<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5v2pkban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a5v2pkban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cookie-solid" {...props}></Icon>
