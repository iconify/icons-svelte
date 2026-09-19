<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg57_081g.css';
import '../../css/a/an7n-_bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xg57_081g"/><path class="an7n-_bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:babel" {...props}></Icon>
