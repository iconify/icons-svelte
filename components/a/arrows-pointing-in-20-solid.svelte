<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxineb4qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rxineb4qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-pointing-in-20-solid" {...props}></Icon>
