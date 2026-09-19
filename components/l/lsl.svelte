<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6dknbc5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":377,"height":512};
const content = `<path class="w6dknbc5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lsl" {...props}></Icon>
