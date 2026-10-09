<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1w0d8d4j.css';
import '../../css/i/i0y7ncbnv.css';
import '../../css/b/bxzxb8v8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p1w0d8d4j"/><path class="i0y7ncbnv"/><path class="bxzxb8v8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-alert-48" {...props}></Icon>
