<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dezwopb-j.css';
import '../../css/p/pv8q02b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dezwopb-j"/><path class="pv8q02b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-minus-48" {...props}></Icon>
