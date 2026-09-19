<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4m_vv5ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x4m_vv5ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:bookmark-fill" {...props}></Icon>
