<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n221nccry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n221nccry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:browser-chrome" {...props}></Icon>
