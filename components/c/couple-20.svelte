<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjz7p6x4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tjz7p6x4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:couple-20" {...props}></Icon>
