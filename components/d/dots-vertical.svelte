<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yke3jhb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yke3jhb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:dots-vertical" {...props}></Icon>
