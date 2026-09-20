<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw-430x6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw-430x6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flame-off" {...props}></Icon>
