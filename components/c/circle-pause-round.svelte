<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzostfs0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzostfs0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-pause-round" {...props}></Icon>
