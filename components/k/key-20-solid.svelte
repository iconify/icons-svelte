<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-l4m5bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n-l4m5bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:key-20-solid" {...props}></Icon>
