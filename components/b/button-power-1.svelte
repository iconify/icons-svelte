<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca5-epbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ca5-epbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:button-power-1" {...props}></Icon>
