<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvrsq3era.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="cvrsq3era"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:head-side-cough-slash" {...props}></Icon>
