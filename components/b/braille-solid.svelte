<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3ccoib0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o3ccoib0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:braille-solid" {...props}></Icon>
