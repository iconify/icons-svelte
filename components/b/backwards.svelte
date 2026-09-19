<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgnj9kbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xgnj9kbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:backwards" {...props}></Icon>
