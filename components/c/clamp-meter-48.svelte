<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muwzxbc8x.css';
import '../../css/o/okfg1bcol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="muwzxbc8x"/><path class="okfg1bcol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clamp-meter-48" {...props}></Icon>
