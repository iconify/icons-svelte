<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgfp6ccio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cgfp6ccio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:plus-cross" {...props}></Icon>
