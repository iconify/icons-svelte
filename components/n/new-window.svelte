<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzrf_m8nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzrf_m8nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:new-window" {...props}></Icon>
