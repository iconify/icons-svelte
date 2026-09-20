<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ono6gbiiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ono6gbiiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gcc" {...props}></Icon>
