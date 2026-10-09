<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhf9xbb9t.css';
import '../../css/x/xnv-ktb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yhf9xbb9t"/><path class="xnv-ktb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badge-48-bold" {...props}></Icon>
