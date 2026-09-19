<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkr_blxgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hkr_blxgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-long-right-20-solid" {...props}></Icon>
