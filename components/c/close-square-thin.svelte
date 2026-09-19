<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7tua87xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7tua87xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-square-thin" {...props}></Icon>
