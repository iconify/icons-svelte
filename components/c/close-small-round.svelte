<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og742qsmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og742qsmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:close-small-round" {...props}></Icon>
