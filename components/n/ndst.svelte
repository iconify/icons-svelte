<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmyfq_blj.css';
import '../../css/a/a28a78bjh.css';
import '../../css/m/m2_srvnyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tmyfq_blj"/><path class="a28a78bjh"/><path class="m2_srvnyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ndst" {...props}></Icon>
