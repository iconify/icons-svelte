<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc85k4qnp.css';
import '../../css/m/mozg7z0hf.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/u/usozxnbrm.css';
import '../../css/q/qkplhcbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="uc85k4qnp"/><path class="mozg7z0hf"/><g class="kdz4acc8r"><circle class="usozxnbrm"/><path class="qkplhcbct"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:regional-indicator-o" {...props}></Icon>
