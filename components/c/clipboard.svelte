<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w22f1_bsl.css';
import '../../css/c/cyx6qvb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w22f1_bsl"/><path class="cyx6qvb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:clipboard" {...props}></Icon>
