<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9q_z2bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h9q_z2bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chess-knight-solid" {...props}></Icon>
