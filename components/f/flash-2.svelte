<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtvfy5lwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rtvfy5lwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flash-2" {...props}></Icon>
