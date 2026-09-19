<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwk2m_bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lwk2m_bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-asia-australia-20-solid" {...props}></Icon>
