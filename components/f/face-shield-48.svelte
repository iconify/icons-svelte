<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-z7esbav.css';
import '../../css/x/xpsvsqb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d-z7esbav"/><path class="xpsvsqb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:face-shield-48" {...props}></Icon>
