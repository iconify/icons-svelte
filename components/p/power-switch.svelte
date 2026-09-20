<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktc-_ac_k.css';
import '../../css/p/pasu78bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ktc-_ac_k"/><path class="pasu78bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:power-switch" {...props}></Icon>
