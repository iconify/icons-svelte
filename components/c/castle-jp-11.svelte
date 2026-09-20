<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-bsaz-tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="m-bsaz-tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:castle-jp-11" {...props}></Icon>
