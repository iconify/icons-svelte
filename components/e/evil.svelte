<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0drj3h3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l0drj3h3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:evil" {...props}></Icon>
