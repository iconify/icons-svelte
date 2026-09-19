<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvwej7una.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvwej7una"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:quote-right-alt" {...props}></Icon>
