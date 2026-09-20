<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/degyop8_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="degyop8_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-square-left-filled" {...props}></Icon>
