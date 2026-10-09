<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7yq16b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u7yq16b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bat-20-bold" {...props}></Icon>
