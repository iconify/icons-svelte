<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxqvldbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxqvldbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:roocode" {...props}></Icon>
