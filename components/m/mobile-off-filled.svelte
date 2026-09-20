<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0gpw2vbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n0gpw2vbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mobile-off-filled" {...props}></Icon>
