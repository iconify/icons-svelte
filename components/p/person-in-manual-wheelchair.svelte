<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp9wi3bpj.css';
import '../../css/i/ie7lpxbir.css';
import '../../css/q/qpr0x4hrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zp9wi3bpj"/><path class="ie7lpxbir"/><path class="qpr0x4hrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-in-manual-wheelchair" {...props}></Icon>
