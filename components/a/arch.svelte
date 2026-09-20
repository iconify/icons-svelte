<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teh5i7b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teh5i7b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arch" {...props}></Icon>
