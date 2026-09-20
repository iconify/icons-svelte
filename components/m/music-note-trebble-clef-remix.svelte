<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e84jpyb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e84jpyb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:music-note-trebble-clef-remix" {...props}></Icon>
