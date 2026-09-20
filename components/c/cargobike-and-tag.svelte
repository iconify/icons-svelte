<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv0nwbbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fv0nwbbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cargobike-and-tag" {...props}></Icon>
