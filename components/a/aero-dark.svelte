<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxtk6mbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":55,"height":20};
const content = `<path clip-rule="evenodd" class="cxtk6mbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aero-dark" {...props}></Icon>
