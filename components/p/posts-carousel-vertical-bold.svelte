<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcxpyny9b.css';
import '../../css/t/tslomuedm.css';
import '../../css/y/yjypexard.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcxpyny9b"/><path class="tslomuedm"/><path class="yjypexard"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-vertical-bold" {...props}></Icon>
