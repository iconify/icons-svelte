<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eltptsb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eltptsb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:hand-point-up" {...props}></Icon>
