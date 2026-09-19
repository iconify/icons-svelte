<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etaycyb8r.css';
import '../../css/y/yd56p_bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="etaycyb8r"/><circle class="yd56p_bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:paw" {...props}></Icon>
