<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlb-sobmx.css';
import '../../css/f/fv0846l_k.css';
import '../../css/m/m_fk-ibei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlb-sobmx"/><path class="fv0846l_k"/><path class="m_fk-ibei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cel" {...props}></Icon>
