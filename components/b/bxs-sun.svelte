<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amj4dacdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amj4dacdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-sun" {...props}></Icon>
