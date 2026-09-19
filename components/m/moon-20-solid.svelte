<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u60y3o5nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u60y3o5nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:moon-20-solid" {...props}></Icon>
