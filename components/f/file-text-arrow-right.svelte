<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_9sbvicc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_9sbvicc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-text-arrow-right" {...props}></Icon>
