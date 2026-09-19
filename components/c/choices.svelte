<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf72p_bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vf72p_bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:choices" {...props}></Icon>
