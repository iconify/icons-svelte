<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-kvwzx-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x-kvwzx-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:pause-circle" {...props}></Icon>
