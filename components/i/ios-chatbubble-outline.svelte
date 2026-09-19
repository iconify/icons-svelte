<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3poo6bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3poo6bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-chatbubble-outline" {...props}></Icon>
