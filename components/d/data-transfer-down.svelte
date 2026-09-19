<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs4i_ac-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cs4i_ac-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:data-transfer-down" {...props}></Icon>
