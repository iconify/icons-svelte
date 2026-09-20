<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1vcuxbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1vcuxbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-d3" {...props}></Icon>
