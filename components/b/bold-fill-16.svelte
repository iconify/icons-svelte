<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec_1s8bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ec_1s8bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bold-fill-16" {...props}></Icon>
