<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewj65icda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="ewj65icda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:metube" {...props}></Icon>
