<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fws0xbbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fws0xbbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dollar-sign-solid" {...props}></Icon>
