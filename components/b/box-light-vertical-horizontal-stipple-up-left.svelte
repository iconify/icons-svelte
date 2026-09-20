<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x76j6m_vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="x76j6m_vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-horizontal-stipple-up-left" {...props}></Icon>
