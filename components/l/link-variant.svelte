<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amgwwsl6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amgwwsl6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-variant" {...props}></Icon>
