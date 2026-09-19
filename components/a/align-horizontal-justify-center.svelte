<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_hz5eaxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_hz5eaxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-horizontal-justify-center" {...props}></Icon>
