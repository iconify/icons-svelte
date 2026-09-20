<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwyn26gpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwyn26gpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:retro-pc-solid" {...props}></Icon>
