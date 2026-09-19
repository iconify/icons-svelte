<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a122dzxck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a122dzxck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cube-three" {...props}></Icon>
