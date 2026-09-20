<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjk-yt08k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjk-yt08k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:radio-retro-bold" {...props}></Icon>
