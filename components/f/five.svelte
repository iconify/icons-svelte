<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i975fgb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i975fgb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:five" {...props}></Icon>
