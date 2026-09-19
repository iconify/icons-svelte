<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tze189b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="tze189b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bing" {...props}></Icon>
