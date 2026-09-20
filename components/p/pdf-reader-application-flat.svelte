<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj1mfwsdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lj1mfwsdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:pdf-reader-application-flat" {...props}></Icon>
