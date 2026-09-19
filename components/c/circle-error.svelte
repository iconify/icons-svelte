<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a84m_v2tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="a84m_v2tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-error" {...props}></Icon>
