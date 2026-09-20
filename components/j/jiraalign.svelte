<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l42ge3b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="l42ge3b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jiraalign" {...props}></Icon>
