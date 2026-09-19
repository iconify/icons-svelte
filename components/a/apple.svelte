<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fef3nobpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fef3nobpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:apple" {...props}></Icon>
