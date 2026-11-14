<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inord5bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":82,"height":82,"top":0.727};
const content = `<path class="inord5bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:open-design" {...props}></Icon>
