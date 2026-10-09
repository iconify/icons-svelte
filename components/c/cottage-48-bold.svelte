<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svn20mxkr.css';
import '../../css/l/l-f6ssbaf.css';
import '../../css/r/ra1t7sbvx.css';
import '../../css/q/qam-_kbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="svn20mxkr"/><path class="l-f6ssbaf"/><path class="ra1t7sbvx"/><path class="qam-_kbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cottage-48-bold" {...props}></Icon>
