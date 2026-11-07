<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy2kejbyw.css';
import '../../css/j/j-36nlbdh.css';
import '../../css/h/hxvqwbbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iy2kejbyw"/><path class="j-36nlbdh"/><path class="hxvqwbbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-minimalistic-bold-duotone" {...props}></Icon>
