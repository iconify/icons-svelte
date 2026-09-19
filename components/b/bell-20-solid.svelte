<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp6ev7bnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jp6ev7bnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-20-solid" {...props}></Icon>
