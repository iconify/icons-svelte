<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s83rnnssr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s83rnnssr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:arrow-thick-left" {...props}></Icon>
