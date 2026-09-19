<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2h6o6bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e2h6o6bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:move" {...props}></Icon>
