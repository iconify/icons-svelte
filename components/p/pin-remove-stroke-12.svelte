<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_hoj2etx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m_hoj2etx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pin-remove-stroke-12" {...props}></Icon>
