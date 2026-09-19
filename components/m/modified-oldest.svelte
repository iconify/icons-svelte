<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0g_v6b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l0g_v6b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:modified-oldest" {...props}></Icon>
