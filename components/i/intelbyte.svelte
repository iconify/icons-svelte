<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjqb2rzwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="kjqb2rzwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:intelbyte" {...props}></Icon>
