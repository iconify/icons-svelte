<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfdoik__w.css';
import '../../css/m/m_qerhonx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kfdoik__w"/><path class="m_qerhonx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:import-bold" {...props}></Icon>
