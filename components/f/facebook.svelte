<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-h9onb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q-h9onb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:facebook" {...props}></Icon>
