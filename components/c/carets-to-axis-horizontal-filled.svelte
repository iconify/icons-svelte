<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2m_w_n-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2m_w_n-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carets-to-axis-horizontal-filled" {...props}></Icon>
