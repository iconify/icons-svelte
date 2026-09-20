<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6_3nkbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6_3nkbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eraser" {...props}></Icon>
