<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3n9mrxup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3n9mrxup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:night-club-disco-ball-1" {...props}></Icon>
