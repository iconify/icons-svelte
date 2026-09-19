<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np_7-4bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="np_7-4bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:head-side-cough-slash" {...props}></Icon>
