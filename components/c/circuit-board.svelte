<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kheaoj4ys.css';
import '../../css/t/t_glypoyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kheaoj4ys"/><path class="t_glypoyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circuit-board" {...props}></Icon>
