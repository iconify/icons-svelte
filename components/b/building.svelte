<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u__b9iwlh.css';
import '../../css/w/wqtak9bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u__b9iwlh"/><path class="wqtak9bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:building" {...props}></Icon>
