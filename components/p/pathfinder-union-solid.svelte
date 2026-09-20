<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs5vxub9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gs5vxub9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pathfinder-union-solid" {...props}></Icon>
