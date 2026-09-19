<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh1flfbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="bh1flfbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3-center-left-20-solid" {...props}></Icon>
