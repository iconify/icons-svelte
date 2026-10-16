<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jycek3qdf.css';
import '../../css/a/aow2a9b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jycek3qdf"/><path class="aow2a9b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-cross-48-bold" {...props}></Icon>
