<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0vh8rd7c.css';
import '../../css/g/go-hdki3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0vh8rd7c"/><path class="go-hdki3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:chat" {...props}></Icon>
