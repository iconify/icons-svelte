<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt6m_qdhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="mt6m_qdhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:pinterest" {...props}></Icon>
