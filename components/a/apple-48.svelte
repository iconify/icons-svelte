<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1yx6v2_d.css';
import '../../css/t/tds6hxauo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z1yx6v2_d"/><path class="tds6hxauo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apple-48" {...props}></Icon>
