<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb9uslyzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mb9uslyzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kali-linux" {...props}></Icon>
