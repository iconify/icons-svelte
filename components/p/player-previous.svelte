<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqxt5abhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqxt5abhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-previous" {...props}></Icon>
