<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvj5u7dat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bvj5u7dat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:git" {...props}></Icon>
