<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_r5p_b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_r5p_b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:beaker" {...props}></Icon>
