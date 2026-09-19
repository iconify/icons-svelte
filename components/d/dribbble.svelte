<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1v3pblxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q1v3pblxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:dribbble" {...props}></Icon>
