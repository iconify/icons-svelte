<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6sho1bhy.css';
import '../../css/l/lhu4h4qes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q6sho1bhy"/><path class="lhu4h4qes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:purchase" {...props}></Icon>
