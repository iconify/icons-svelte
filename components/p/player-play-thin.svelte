<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f62xxfveg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f62xxfveg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-play-thin" {...props}></Icon>
