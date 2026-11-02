<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot7fqob2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot7fqob2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-1-fill" {...props}></Icon>
