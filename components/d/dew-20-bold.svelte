<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6or-r9if.css';
import '../../css/g/ggfao8bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p6or-r9if"/><path class="ggfao8bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dew-20-bold" {...props}></Icon>
