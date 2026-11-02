<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc3t8iprc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc3t8iprc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layers-minus-fill" {...props}></Icon>
