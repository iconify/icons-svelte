<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deb2onban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="deb2onban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:music-solid" {...props}></Icon>
