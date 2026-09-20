<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_83hibdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m_83hibdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:ellipsis-16" {...props}></Icon>
