<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y-3qzwbmz.css';
import '../../css/b/b48b5ubwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":81,"height":81};
const content = `<g class="ft5dv1b6b"><path class="y-3qzwbmz"/><path class="b48b5ubwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lottiefiles" {...props}></Icon>
