<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4v9t2bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4v9t2bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:handshake" {...props}></Icon>
