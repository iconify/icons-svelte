<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8bzgz7vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b8bzgz7vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:download-computer" {...props}></Icon>
