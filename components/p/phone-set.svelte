<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1t2jvjmb.css';
import '../../css/t/tizvf-b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="u1t2jvjmb"/><path class="tizvf-b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:phone-set" {...props}></Icon>
