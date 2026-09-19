<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsadl7bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dsadl7bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:postcard" {...props}></Icon>
