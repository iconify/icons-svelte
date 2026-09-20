<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbm6x22ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbm6x22ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bezier-filled" {...props}></Icon>
