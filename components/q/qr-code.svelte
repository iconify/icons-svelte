<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5-xvachn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c5-xvachn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:qr-code" {...props}></Icon>
