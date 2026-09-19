<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbfp1bcso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbfp1bcso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-plus-01" {...props}></Icon>
