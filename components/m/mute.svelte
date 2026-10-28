<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i55-vdeam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i55-vdeam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:mute" {...props}></Icon>
