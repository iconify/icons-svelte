<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3gv0lbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x3gv0lbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:netbeans-wordmark" {...props}></Icon>
