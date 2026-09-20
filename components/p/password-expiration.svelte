<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcgh8u5lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcgh8u5lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:password-expiration" {...props}></Icon>
