<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzhcoetij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzhcoetij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:prescription-line" {...props}></Icon>
