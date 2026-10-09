<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0gxl0bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d0gxl0bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-right-48" {...props}></Icon>
