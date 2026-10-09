<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzq1-xdkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jzq1-xdkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:quarry-48" {...props}></Icon>
