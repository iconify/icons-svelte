<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq_w9hbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq_w9hbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mxc" {...props}></Icon>
