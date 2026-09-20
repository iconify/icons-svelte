<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar164sbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar164sbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-cny-2-line" {...props}></Icon>
