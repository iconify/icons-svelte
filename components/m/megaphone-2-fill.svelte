<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp6z-4mxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp6z-4mxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:megaphone-2-fill" {...props}></Icon>
