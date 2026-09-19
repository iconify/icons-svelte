<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3290zb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x3290zb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-right-20-solid" {...props}></Icon>
