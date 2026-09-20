<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq6gbbbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cq6gbbbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:christ-the-redeemer-line" {...props}></Icon>
