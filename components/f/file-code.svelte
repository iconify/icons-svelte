<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiyst2b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="wiyst2b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:file-code" {...props}></Icon>
