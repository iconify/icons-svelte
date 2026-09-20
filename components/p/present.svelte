<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxn6f5kct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dxn6f5kct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:present" {...props}></Icon>
