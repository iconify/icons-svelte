<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0l9478oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f0l9478oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:come" {...props}></Icon>
