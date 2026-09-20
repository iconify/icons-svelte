<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbnhd6bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbnhd6bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:group" {...props}></Icon>
