<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm5r9sbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1568,"height":1568};
const content = `<path class="xm5r9sbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:maybank" {...props}></Icon>
