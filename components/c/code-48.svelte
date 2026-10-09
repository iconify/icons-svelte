<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm_-eumxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sm_-eumxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:code-48" {...props}></Icon>
