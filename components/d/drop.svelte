<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_m8tpdhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m_m8tpdhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:drop" {...props}></Icon>
