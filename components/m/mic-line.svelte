<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxdx7ij6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxdx7ij6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:mic-line" {...props}></Icon>
