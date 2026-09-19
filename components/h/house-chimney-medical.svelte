<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck8_mw97s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ck8_mw97s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house-chimney-medical" {...props}></Icon>
