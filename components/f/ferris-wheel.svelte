<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl4zbepqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl4zbepqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ferris-wheel" {...props}></Icon>
