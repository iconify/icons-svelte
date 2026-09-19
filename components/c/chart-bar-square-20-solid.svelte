<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vws5lwbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vws5lwbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chart-bar-square-20-solid" {...props}></Icon>
