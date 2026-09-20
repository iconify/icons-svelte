<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as8m_2_xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="as8m_2_xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:file-plus-outline" {...props}></Icon>
