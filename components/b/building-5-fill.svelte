<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi4a8_62c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi4a8_62c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-5-fill" {...props}></Icon>
