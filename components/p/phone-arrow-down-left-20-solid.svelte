<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urjfcxktu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="urjfcxktu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:phone-arrow-down-left-20-solid" {...props}></Icon>
