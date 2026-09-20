<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwf-2hout.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwf-2hout"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dashboard-3-line" {...props}></Icon>
