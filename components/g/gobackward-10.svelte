<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy4mpxe2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zy4mpxe2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gobackward-10" {...props}></Icon>
