<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s02nxkbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="s02nxkbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:handshake-alt" {...props}></Icon>
