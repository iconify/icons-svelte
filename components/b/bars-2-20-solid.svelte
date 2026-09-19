<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtyv3plye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="qtyv3plye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-2-20-solid" {...props}></Icon>
