<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1x60zbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":55,"height":20};
const content = `<path clip-rule="evenodd" class="i1x60zbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aero-light" {...props}></Icon>
