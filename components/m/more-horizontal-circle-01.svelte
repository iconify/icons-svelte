<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_gjrgbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_gjrgbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:more-horizontal-circle-01" {...props}></Icon>
