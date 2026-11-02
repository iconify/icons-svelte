<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuu733bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuu733bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:az-sort-ascending-letters-line" {...props}></Icon>
