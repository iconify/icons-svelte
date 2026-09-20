<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylj5lsb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylj5lsb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fence-off" {...props}></Icon>
