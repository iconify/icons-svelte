<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eagy8eb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="eagy8eb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:karatelabs" {...props}></Icon>
