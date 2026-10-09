<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmj85obju.css';
import '../../css/o/oj51yuuri.css';
import '../../css/d/dede64x5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zmj85obju"/><path class="oj51yuuri"/><path class="dede64x5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:global-warming-48" {...props}></Icon>
