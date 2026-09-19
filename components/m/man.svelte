<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4klw5k7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t4klw5k7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:man" {...props}></Icon>
