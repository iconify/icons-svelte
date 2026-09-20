<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpd0j0tem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpd0j0tem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-trend-up-duotone" {...props}></Icon>
