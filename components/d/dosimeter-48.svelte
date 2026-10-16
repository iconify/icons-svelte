<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qst8sacvr.css';
import '../../css/n/ncpk28ife.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qst8sacvr"/><path class="ncpk28ife"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dosimeter-48" {...props}></Icon>
