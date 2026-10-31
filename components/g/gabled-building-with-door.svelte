<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_hc_3f3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m_hc_3f3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gabled-building-with-door" {...props}></Icon>
