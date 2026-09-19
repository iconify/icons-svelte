<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tum1hdh1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tum1hdh1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:planet" {...props}></Icon>
