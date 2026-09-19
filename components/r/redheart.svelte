<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x880s-uzh.css';
import '../../css/t/t5_14z-jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x880s-uzh"/><path class="t5_14z-jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:redheart" {...props}></Icon>
