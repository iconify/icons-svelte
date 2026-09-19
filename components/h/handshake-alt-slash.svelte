<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0ox3b4ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="f0ox3b4ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:handshake-alt-slash" {...props}></Icon>
