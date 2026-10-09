<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-xqmce0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r-xqmce0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pause-48" {...props}></Icon>
