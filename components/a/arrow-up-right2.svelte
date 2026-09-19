<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_6j5db4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e_6j5db4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-up-right2" {...props}></Icon>
