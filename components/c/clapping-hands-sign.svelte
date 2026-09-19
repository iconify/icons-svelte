<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_xckbald.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m_xckbald"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:clapping-hands-sign" {...props}></Icon>
