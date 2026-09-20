<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt882wm4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt882wm4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:color-palette-2-bold" {...props}></Icon>
