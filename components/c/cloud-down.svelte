<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_g8aobdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="m_g8aobdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:cloud-down" {...props}></Icon>
