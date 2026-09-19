<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du3ndgb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="du3ndgb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:goblet" {...props}></Icon>
