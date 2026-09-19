<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzzzhdbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mzzzhdbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:backward-20-solid" {...props}></Icon>
