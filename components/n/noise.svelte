<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoxr_xwde.css';
import '../../css/v/vvuprkbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b yoxr_xwde"/><path class="b vvuprkbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:noise" {...props}></Icon>
