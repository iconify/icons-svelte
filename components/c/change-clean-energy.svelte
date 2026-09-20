<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkkkvn-jc.css';
import '../../css/v/vnaypctab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dkkkvn-jc"/><path class="vnaypctab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:change-clean-energy" {...props}></Icon>
