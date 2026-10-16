<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3me-4caq.css';
import '../../css/w/wgtq23b2b.css';
import '../../css/i/i9p3igbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c3me-4caq"/><path class="wgtq23b2b"/><path class="i9p3igbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-cog-20" {...props}></Icon>
