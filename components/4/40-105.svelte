<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kniyv1net.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":448};
const content = `<path class="kniyv1net"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:40-105" {...props}></Icon>
