<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg8ren7cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cg8ren7cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:largeorangediamond" {...props}></Icon>
