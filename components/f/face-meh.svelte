<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fytkei63w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fytkei63w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-meh" {...props}></Icon>
