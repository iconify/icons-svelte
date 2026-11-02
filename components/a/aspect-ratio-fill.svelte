<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld8o_abgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld8o_abgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aspect-ratio-fill" {...props}></Icon>
