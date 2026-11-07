<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlavk1bjm.css';
import '../../css/p/phap5z8zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xlavk1bjm"/><path class="phap5z8zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pie-chart-outline" {...props}></Icon>
