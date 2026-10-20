<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inudf1erv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="inudf1erv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:option-key-20" {...props}></Icon>
