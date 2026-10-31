<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuc2r_fef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuc2r_fef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:grid-round" {...props}></Icon>
