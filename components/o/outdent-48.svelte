<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyc3k4bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iyc3k4bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:outdent-48" {...props}></Icon>
