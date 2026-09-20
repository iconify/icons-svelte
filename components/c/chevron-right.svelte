<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah7_xrbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ah7_xrbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:chevron-right" {...props}></Icon>
