<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0x4f1bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n0x4f1bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:banknotes-20-solid" {...props}></Icon>
