<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0ylx01sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o0ylx01sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:level-none-ltr" {...props}></Icon>
