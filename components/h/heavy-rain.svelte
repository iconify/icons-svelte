<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzgfo0ilr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dzgfo0ilr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:heavy-rain" {...props}></Icon>
