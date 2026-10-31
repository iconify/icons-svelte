<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzp-m_bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzp-m_bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:droplet-fill-round" {...props}></Icon>
