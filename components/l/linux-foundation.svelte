<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo8h1vk8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uo8h1vk8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:linux-foundation" {...props}></Icon>
