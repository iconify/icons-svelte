<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnt2i8b5v.css';
import '../../css/p/p2p39tb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jnt2i8b5v"/><path class="p2p39tb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:godot-wordmark" {...props}></Icon>
