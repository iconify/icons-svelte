<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omu23ub3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omu23ub3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ferris-wheel" {...props}></Icon>
