<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrxun4d8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mrxun4d8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-snow" {...props}></Icon>
