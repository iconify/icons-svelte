<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpcp248iu.css';
import '../../css/w/wp7bgyt0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dpcp248iu"/><path class="wp7bgyt0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:coin-pound" {...props}></Icon>
