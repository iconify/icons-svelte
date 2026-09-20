<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa0z2b_vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa0z2b_vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:laptop" {...props}></Icon>
