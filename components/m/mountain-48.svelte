<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d33itbbpi.css';
import '../../css/j/jbxq4-b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d33itbbpi"/><path class="jbxq4-b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-48" {...props}></Icon>
