<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtz_hcc5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rtz_hcc5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-check-bold" {...props}></Icon>
