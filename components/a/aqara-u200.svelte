<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1iy2g3vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1iy2g3vf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-u200" {...props}></Icon>
