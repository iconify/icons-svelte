<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcrkei-7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vcrkei-7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:add-solid" {...props}></Icon>
