<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cilo2uhhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cilo2uhhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:letter-spacing-fill" {...props}></Icon>
