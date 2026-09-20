<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6dy_r2wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6dy_r2wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:react-solid" {...props}></Icon>
