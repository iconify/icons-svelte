<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eedgg_uqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eedgg_uqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mouse-click" {...props}></Icon>
