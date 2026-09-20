<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnb9i2bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wnb9i2bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:facebook-messenger" {...props}></Icon>
