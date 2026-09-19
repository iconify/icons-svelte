<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfk4z3biw.css';
import '../../css/y/ygf9v4-fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfk4z3biw"/><path class="ygf9v4-fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-star" {...props}></Icon>
