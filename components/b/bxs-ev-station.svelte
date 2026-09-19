<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxctd4bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxctd4bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-ev-station" {...props}></Icon>
