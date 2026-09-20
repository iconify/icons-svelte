<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzl577bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzl577bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-large-bold" {...props}></Icon>
