<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf7p2-bce.css';
import '../../css/i/idjuv0btd.css';
import '../../css/y/y7pnu2bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cf7p2-bce"><path class="idjuv0btd"/><path class="y7pnu2bvg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:audio" {...props}></Icon>
