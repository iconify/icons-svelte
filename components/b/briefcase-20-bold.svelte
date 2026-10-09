<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_8jrujkz.css';
import '../../css/c/cqfb17bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c_8jrujkz"/><path class="cqfb17bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:briefcase-20-bold" {...props}></Icon>
