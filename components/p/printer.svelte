<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cad7fybxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cad7fybxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:printer" {...props}></Icon>
