<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saaufmbsj.css';
import '../../css/k/kl-9_wbua.css';
import '../../css/p/pgfaj-tpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="saaufmbsj"/><path class="kl-9_wbua"/><path class="pgfaj-tpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:photography-camera-1" {...props}></Icon>
