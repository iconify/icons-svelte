<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juaf2_1xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="juaf2_1xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:intersex-symbol-solid" {...props}></Icon>
