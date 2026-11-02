<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxq0h2b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxq0h2b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layer-fill" {...props}></Icon>
