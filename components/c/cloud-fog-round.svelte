<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2m_4_bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2m_4_bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-fog-round" {...props}></Icon>
