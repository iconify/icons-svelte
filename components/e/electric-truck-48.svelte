<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xujk5fdpi.css';
import '../../css/e/e5asi9aud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xujk5fdpi"/><path class="e5asi9aud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-truck-48" {...props}></Icon>
