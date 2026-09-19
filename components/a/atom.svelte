<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdp02hb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="wdp02hb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:atom" {...props}></Icon>
