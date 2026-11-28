<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_movwbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m_movwbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:rock-tall-thin" {...props}></Icon>
