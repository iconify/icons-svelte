<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh6gu7bbw.css';
import '../../css/u/utcfm6g2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nh6gu7bbw"/><path class="utcfm6g2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:backpack-48" {...props}></Icon>
