<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-osqbb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w-osqbb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:map-16" {...props}></Icon>
