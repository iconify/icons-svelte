<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxt8ivbsc.css';
import '../../css/c/ckqvl2v2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mxt8ivbsc"/><circle class="ckqvl2v2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:help-outline" {...props}></Icon>
