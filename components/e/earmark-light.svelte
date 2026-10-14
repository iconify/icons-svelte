<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w79h7j-7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":180,"height":180};
const content = `<path class="w79h7j-7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:earmark-light" {...props}></Icon>
