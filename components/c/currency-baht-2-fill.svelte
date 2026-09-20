<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdfi2l-qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdfi2l-qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-baht-2-fill" {...props}></Icon>
