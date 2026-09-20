<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0-j8u8ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0-j8u8ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-remove" {...props}></Icon>
