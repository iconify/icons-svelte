<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd-j1738m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dd-j1738m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:maximize-48" {...props}></Icon>
