<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do_cy5bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do_cy5bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-firebase" {...props}></Icon>
