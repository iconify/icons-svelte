<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itc5zdbai.css';
import '../../css/o/o6w0dd8_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="itc5zdbai"/><path class="o6w0dd8_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-circle-filled" {...props}></Icon>
