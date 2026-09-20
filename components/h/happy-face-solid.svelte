<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvtjo-b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fvtjo-b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:happy-face-solid" {...props}></Icon>
