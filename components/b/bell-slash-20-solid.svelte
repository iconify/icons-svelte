<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk_8nrbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rk_8nrbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-slash-20-solid" {...props}></Icon>
