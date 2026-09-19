<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg-d_yb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg-d_yb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevron-up-square" {...props}></Icon>
