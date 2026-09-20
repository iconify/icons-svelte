<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxiqf-86n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxiqf-86n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rainbow" {...props}></Icon>
