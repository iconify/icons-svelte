<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w64l-ub0s.css';
import '../../css/f/f8bjlbjhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w64l-ub0s"/><path class="f8bjlbjhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-down-left-48" {...props}></Icon>
