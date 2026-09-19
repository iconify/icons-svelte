<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr5z6m_rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="wr5z6m_rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:landscape" {...props}></Icon>
