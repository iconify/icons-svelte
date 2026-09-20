<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_ad-m_cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_ad-m_cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pen-lock" {...props}></Icon>
