<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxqq79o5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dxqq79o5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:delta-chat-dark" {...props}></Icon>
