<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_dm8e3xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_dm8e3xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-stack-overflow" {...props}></Icon>
