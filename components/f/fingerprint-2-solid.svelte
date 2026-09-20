<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loncyrbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="loncyrbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fingerprint-2-solid" {...props}></Icon>
