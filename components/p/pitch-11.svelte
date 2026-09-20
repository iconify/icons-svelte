<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_4h3zllq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="m_4h3zllq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:pitch-11" {...props}></Icon>
