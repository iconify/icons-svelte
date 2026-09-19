<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_k2hhb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m_k2hhb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bars-3-bottom-right" {...props}></Icon>
