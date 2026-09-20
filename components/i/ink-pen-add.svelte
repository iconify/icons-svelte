<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz296k4st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dz296k4st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ink-pen-add" {...props}></Icon>
