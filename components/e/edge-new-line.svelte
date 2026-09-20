<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnk_oc_5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnk_oc_5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:edge-new-line" {...props}></Icon>
