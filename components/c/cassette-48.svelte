<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq88i7qnu.css';
import '../../css/c/c_5vdvbsq.css';
import '../../css/o/oqui6zsbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zq88i7qnu"/><path class="c_5vdvbsq"/><path class="oqui6zsbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cassette-48" {...props}></Icon>
