<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw56qbcjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iw56qbcjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:guitar-solid" {...props}></Icon>
