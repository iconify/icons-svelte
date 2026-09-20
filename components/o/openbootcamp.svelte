<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycchbsbfz.css';
import '../../css/n/n0pg1wbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":70,"height":51};
const content = `<ellipse class="ycchbsbfz"/><path clip-rule="evenodd" class="n0pg1wbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openbootcamp" {...props}></Icon>
