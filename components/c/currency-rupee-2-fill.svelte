<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m661uj1fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m661uj1fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-rupee-2-fill" {...props}></Icon>
