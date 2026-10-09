<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh0wmoblc.css';
import '../../css/o/oxbk-rb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qh0wmoblc"/><path class="oxbk-rb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:barrel-48" {...props}></Icon>
