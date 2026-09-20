<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb2axfb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="gb2axfb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rewind" {...props}></Icon>
