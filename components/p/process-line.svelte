<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnea9oquu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dnea9oquu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:process-line" {...props}></Icon>
