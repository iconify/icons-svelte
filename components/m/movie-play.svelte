<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtr2n8b0s.css';
import '../../css/o/o9scry_ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtr2n8b0s"/><path class="o9scry_ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:movie-play" {...props}></Icon>
