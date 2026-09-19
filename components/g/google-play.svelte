<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rovv-r93y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="rovv-r93y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:google-play" {...props}></Icon>
