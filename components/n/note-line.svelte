<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1can7bss.css';
import '../../css/w/wq-h3db8q.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 d1can7bss"/><path class="clr-i-outline clr-i-outline-path-2 wq-h3db8q"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:note-line" {...props}></Icon>
