<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sihs_b4zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sihs_b4zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:coins-round" {...props}></Icon>
