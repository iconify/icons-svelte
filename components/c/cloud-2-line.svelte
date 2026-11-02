<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu76ixbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu76ixbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-2-line" {...props}></Icon>
