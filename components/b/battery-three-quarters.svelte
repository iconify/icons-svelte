<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn36qn67e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bn36qn67e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:battery-three-quarters" {...props}></Icon>
