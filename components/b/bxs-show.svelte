<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vza3v5bem.css';
import '../../css/c/cxpp0lxyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vza3v5bem"/><path class="cxpp0lxyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-show" {...props}></Icon>
