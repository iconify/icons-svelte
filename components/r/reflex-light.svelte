<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sldau_bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":12};
const content = `<path class="sldau_bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:reflex-light" {...props}></Icon>
