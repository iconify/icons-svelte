<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w21eicddf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w21eicddf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-fill" {...props}></Icon>
