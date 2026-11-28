<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfotacrzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qfotacrzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:clock-plus" {...props}></Icon>
