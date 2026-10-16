<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai3gqkb8w.css';
import '../../css/a/aga2wzbcv.css';
import '../../css/b/bgmlxcclc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ai3gqkb8w"/><path class="aga2wzbcv"/><path class="bgmlxcclc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-compressor-20" {...props}></Icon>
