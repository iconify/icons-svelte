<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw43jv51r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw43jv51r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:right-indent" {...props}></Icon>
