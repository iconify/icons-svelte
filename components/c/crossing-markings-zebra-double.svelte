<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqxfqybqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kqxfqybqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:crossing-markings-zebra-double" {...props}></Icon>
