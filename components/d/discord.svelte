<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6j6fiaxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":199};
const content = `<path class="r6j6fiaxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:discord" {...props}></Icon>
