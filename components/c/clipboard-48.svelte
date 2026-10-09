<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-s18fbbr.css';
import '../../css/p/p0vii7b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x-s18fbbr"/><path class="p0vii7b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-48" {...props}></Icon>
