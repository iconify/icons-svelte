<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mheic9b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mheic9b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:guy-cry" {...props}></Icon>
