<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4ko2it3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b4ko2it3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:navigation" {...props}></Icon>
