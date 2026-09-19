<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg7avqbog.css';
import '../../css/d/dnoobir0b.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 fg7avqbog"/><path class="clr-i-outline clr-i-outline-path-2 dnoobir0b"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:export-line" {...props}></Icon>
