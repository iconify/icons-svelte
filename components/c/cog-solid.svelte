<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioq918dwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioq918dwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cog-solid" {...props}></Icon>
