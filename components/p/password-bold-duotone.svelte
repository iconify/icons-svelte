<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvcm_2wyi.css';
import '../../css/o/oqai2m_dh.css';
import '../../css/u/u7dt5acml.css';
import '../../css/v/v2xxlybwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvcm_2wyi"/><path class="oqai2m_dh"/><path class="u7dt5acml"/><path class="v2xxlybwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:password-bold-duotone" {...props}></Icon>
