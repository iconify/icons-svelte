<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy4hlac5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy4hlac5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-67-small" {...props}></Icon>
