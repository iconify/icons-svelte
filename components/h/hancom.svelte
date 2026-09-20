<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxkiydbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2555,"height":810};
const content = `<path class="dxkiydbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hancom" {...props}></Icon>
