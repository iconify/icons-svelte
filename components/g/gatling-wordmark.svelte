<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol2yed01a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ol2yed01a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gatling-wordmark" {...props}></Icon>
