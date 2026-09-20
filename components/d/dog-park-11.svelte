<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9_od2b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="r9_od2b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:dog-park-11" {...props}></Icon>
