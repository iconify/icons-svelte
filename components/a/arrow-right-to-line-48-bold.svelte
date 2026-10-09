<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8_-mvbmk.css';
import '../../css/n/n5nqfww4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x8_-mvbmk"/><path class="n5nqfww4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-right-to-line-48-bold" {...props}></Icon>
