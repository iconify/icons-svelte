<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_y2uo_sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_y2uo_sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:erase" {...props}></Icon>
