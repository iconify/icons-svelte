<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv2q8ftgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dv2q8ftgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-play-fill" {...props}></Icon>
