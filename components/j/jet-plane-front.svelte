<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7c_9fb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v7c_9fb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:jet-plane-front" {...props}></Icon>
