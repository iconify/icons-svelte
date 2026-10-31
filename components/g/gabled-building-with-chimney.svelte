<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgwh5lbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bgwh5lbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gabled-building-with-chimney" {...props}></Icon>
