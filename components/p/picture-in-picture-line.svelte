<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_o_u3b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_o_u3b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:picture-in-picture-line" {...props}></Icon>
