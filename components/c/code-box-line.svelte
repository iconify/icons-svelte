<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-1btabkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-1btabkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:code-box-line" {...props}></Icon>
