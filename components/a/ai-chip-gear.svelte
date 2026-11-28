<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo-sj7iwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo-sj7iwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ai-chip-gear" {...props}></Icon>
