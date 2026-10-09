<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajtnjnklx.css';
import '../../css/s/sb9rsi1bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ajtnjnklx"/><path class="sb9rsi1bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frying-pan-48" {...props}></Icon>
