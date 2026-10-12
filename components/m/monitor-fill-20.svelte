<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdp7o9mju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jdp7o9mju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:monitor-fill-20" {...props}></Icon>
