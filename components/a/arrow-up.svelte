<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm_tybc4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lm_tybc4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:arrow-up" {...props}></Icon>
