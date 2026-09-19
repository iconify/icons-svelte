<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_ocu_pkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p_ocu_pkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:camera-filled" {...props}></Icon>
