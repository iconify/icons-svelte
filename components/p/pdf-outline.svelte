<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_nrcgb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m_nrcgb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pdf-outline" {...props}></Icon>
