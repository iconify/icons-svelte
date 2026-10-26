<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt_lpuqei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1510,"height":1515};
const content = `<path class="xt_lpuqei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pnj" {...props}></Icon>
