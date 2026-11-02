<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xas3exbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xas3exbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bnb-fill" {...props}></Icon>
