<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rasakkbar.css';
import '../../css/k/kthl54b0k.css';
import '../../css/r/r_bgghfih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rasakkbar"/><path class="kthl54b0k"/><path class="r_bgghfih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pie-chart-filled" {...props}></Icon>
