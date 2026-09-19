<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysqt9cbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ysqt9cbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:npm" {...props}></Icon>
