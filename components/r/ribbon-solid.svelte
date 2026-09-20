<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip2jfysyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ip2jfysyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ribbon-solid" {...props}></Icon>
