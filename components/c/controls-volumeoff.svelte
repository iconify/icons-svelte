<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4gnvtuxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p4gnvtuxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:controls-volumeoff" {...props}></Icon>
