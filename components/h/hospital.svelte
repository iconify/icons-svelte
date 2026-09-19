<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wookawbbo.css';
import '../../css/p/p8dgzzb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wookawbbo"/><path class="p8dgzzb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hospital" {...props}></Icon>
