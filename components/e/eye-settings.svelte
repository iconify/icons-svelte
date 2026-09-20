<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv79jnbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv79jnbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-settings" {...props}></Icon>
