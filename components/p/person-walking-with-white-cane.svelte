<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m52ut1_py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m52ut1_py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-with-white-cane" {...props}></Icon>
