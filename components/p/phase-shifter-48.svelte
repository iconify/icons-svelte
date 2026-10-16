<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk1hxdbxp.css';
import '../../css/v/vfx4m_b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wk1hxdbxp"/><path class="vfx4m_b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phase-shifter-48" {...props}></Icon>
