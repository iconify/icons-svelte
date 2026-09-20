<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmnv41bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jmnv41bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bench-with-armrests-and-backrest-with-plaque" {...props}></Icon>
