<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/citnwbcum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="citnwbcum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:fingerprint-2-flat" {...props}></Icon>
