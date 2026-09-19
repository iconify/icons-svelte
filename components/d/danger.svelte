<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlfa2ebbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="dlfa2ebbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:danger" {...props}></Icon>
