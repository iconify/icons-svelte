<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx30rnqyk.css';
import '../../css/g/g-qkl-bcv.css';
import '../../css/e/em089opbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx30rnqyk"/><path class="g-qkl-bcv"/><path class="em089opbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bluetooth-wave-bold" {...props}></Icon>
