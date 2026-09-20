<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0oa4jz6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path clip-rule="evenodd" class="i0oa4jz6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:raycast" {...props}></Icon>
