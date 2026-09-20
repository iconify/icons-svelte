<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozn0_bc3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="ozn0_bc3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:menu-meatballs-1" {...props}></Icon>
