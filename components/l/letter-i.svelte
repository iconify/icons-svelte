<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy5ss_0sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy5ss_0sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-i" {...props}></Icon>
