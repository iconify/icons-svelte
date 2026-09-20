<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2k218b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2k218b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pusher" {...props}></Icon>
