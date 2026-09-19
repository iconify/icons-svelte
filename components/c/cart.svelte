<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsglcjabq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":720,"height":820};
const content = `<path class="dsglcjabq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:cart" {...props}></Icon>
