<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xedufpf4g.css';
import '../../css/p/pfnbi-dgu.css';
import '../../css/r/rnwwcable.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xedufpf4g"/><path class="pfnbi-dgu"/><path class="rnwwcable"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-trading-48" {...props}></Icon>
