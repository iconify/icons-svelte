<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_ho2kyto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_ho2kyto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:music-note-trebble-clef-flat" {...props}></Icon>
