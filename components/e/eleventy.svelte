<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu1wy4b6g.css';
import '../../css/y/yuoo8p78p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tu1wy4b6g"/><path class="yuoo8p78p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:eleventy" {...props}></Icon>
