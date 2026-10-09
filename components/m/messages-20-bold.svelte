<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhq4ynm1t.css';
import '../../css/z/zenhfcbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vhq4ynm1t"/><path class="zenhfcbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:messages-20-bold" {...props}></Icon>
