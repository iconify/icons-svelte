<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hchve7bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hchve7bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:capslock" {...props}></Icon>
