<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfgr-6b4b.css';
import '../../css/q/q93ngmbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zfgr-6b4b"/><path class="q93ngmbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:notebook-48" {...props}></Icon>
