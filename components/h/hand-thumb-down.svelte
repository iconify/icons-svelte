<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh_m7bbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vh_m7bbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:hand-thumb-down" {...props}></Icon>
