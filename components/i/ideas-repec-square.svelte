<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_nj9wwfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="c_nj9wwfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ideas-repec-square" {...props}></Icon>
