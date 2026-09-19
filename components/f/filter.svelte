<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq5rap8vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mq5rap8vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:filter" {...props}></Icon>
