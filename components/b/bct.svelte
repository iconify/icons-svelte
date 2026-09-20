<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt56ufadj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt56ufadj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bct" {...props}></Icon>
