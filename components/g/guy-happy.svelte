<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn1zf-bov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jn1zf-bov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:guy-happy" {...props}></Icon>
