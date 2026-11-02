<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr-ju4bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr-ju4bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:light-line" {...props}></Icon>
