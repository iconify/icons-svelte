<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivwl1-arg.css';
import '../../css/u/uj46r2dkm.css';
import '../../css/m/m_u9wub5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivwl1-arg"/><path class="uj46r2dkm"/><path class="m_u9wub5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:car-bolt" {...props}></Icon>
