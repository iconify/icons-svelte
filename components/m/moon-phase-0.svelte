<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur7o7bbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur7o7bbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-0" {...props}></Icon>
