<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb-xcib8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb-xcib8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:funnel-x" {...props}></Icon>
