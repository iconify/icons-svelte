<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu71a8jkb.css';
import '../../css/a/a6z1s6b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wu71a8jkb"/><path class="a6z1s6b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:generator-48-bold" {...props}></Icon>
