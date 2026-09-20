<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxth-8fty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxth-8fty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:music-note-trebble-clef" {...props}></Icon>
