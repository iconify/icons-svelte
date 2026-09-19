<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqfc6_h8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqfc6_h8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-brightness-half" {...props}></Icon>
