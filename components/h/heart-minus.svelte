<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajpcoobkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajpcoobkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-minus" {...props}></Icon>
