<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wte_qbcjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="wte_qbcjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:braille" {...props}></Icon>
