<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvdwg8b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvdwg8b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:desktop-alt" {...props}></Icon>
