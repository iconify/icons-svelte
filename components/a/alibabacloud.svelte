<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_b_9cx1c.css';
import '../../css/i/iejop6bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_b_9cx1c"/><path class="iejop6bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alibabacloud" {...props}></Icon>
