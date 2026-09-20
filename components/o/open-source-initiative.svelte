<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk4mz_b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk4mz_b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:open-source-initiative" {...props}></Icon>
