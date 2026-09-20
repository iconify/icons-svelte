<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9_1y9bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="i9_1y9bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:number-sign" {...props}></Icon>
