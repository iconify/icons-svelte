<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klb9dw5dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="klb9dw5dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:medical-cross-symbol-flat" {...props}></Icon>
