<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf9t8jb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf9t8jb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:angle-double-right" {...props}></Icon>
