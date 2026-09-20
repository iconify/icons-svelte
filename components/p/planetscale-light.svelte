<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1_al-bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x1_al-bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:planetscale-light" {...props}></Icon>
