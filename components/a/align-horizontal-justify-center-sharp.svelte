<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnu-rxwwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnu-rxwwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-horizontal-justify-center-sharp" {...props}></Icon>
