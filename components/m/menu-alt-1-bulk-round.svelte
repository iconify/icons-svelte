<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs5m_2bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs5m_2bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-alt-1-bulk-round" {...props}></Icon>
