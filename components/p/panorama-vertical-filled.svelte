<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh4nc23vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oh4nc23vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:panorama-vertical-filled" {...props}></Icon>
