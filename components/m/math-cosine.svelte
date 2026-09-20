<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amrhr5zub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amrhr5zub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:math-cosine" {...props}></Icon>
