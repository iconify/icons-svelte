<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8m_pv4an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r8m_pv4an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hand-thumbs-down-fill" {...props}></Icon>
