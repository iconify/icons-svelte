<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eek12hbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eek12hbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:label" {...props}></Icon>
