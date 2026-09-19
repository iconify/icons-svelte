<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/remi2-b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="remi2-b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-error-circle" {...props}></Icon>
