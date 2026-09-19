<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mda75gbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mda75gbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:right-arrow-square" {...props}></Icon>
