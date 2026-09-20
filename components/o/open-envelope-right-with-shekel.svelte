<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_6nx6bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m_6nx6bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-envelope-right-with-shekel" {...props}></Icon>
