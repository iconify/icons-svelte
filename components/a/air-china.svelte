<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi2x4tq6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi2x4tq6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:air-china" {...props}></Icon>
