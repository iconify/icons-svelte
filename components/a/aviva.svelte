<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl59vwg3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":161,"height":56};
const content = `<path clip-rule="evenodd" class="xl59vwg3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aviva" {...props}></Icon>
