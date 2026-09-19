<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r93y31_uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r93y31_uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:music-outline" {...props}></Icon>
