<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzje2pbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xzje2pbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:circle-dashed-48" {...props}></Icon>
