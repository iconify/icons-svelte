<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewk5jvbls.css';
import '../../css/h/hok5llblz.css';
import '../../css/d/d3a09urjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":226};
const content = `<path class="ewk5jvbls"/><path class="hok5llblz"/><path class="d3a09urjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:netlify" {...props}></Icon>
