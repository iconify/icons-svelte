<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir2h2kauu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir2h2kauu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-arrow-left" {...props}></Icon>
