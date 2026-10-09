<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqtu52b6d.css';
import '../../css/k/k0ztijb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aqtu52b6d"/><path class="k0ztijb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-island-20" {...props}></Icon>
