<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2do23bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2do23bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:kingkey-100-tower-line" {...props}></Icon>
