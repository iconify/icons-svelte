<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prw1abc4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="prw1abc4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:play-20-solid" {...props}></Icon>
