<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6ecf736e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="m6ecf736e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:renren" {...props}></Icon>
