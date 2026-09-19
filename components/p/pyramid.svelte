<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq6lq7k0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq6lq7k0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:pyramid" {...props}></Icon>
