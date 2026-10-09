<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rye9qojth.css';
import '../../css/p/puz5jibvr.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rye9qojth"/><path class="puz5jibvr"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pets-allowed-20" {...props}></Icon>
