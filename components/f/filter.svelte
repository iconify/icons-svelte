<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eht0_oe3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="eht0_oe3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:filter" {...props}></Icon>
