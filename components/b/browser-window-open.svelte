<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh29bfbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eh29bfbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:browser-window-open" {...props}></Icon>
