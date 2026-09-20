<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrx0drblt.css';
import '../../css/k/kvk09bbcv.css';
import '../../css/c/cv18w6a5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="mrx0drblt"/><circle class="kvk09bbcv"/><path class="cv18w6a5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:divide" {...props}></Icon>
