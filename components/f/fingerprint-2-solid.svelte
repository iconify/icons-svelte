<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc0js2y2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fc0js2y2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:fingerprint-2-solid" {...props}></Icon>
