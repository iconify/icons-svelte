<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqvup9b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gqvup9b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pathfinder-square-exclude-remix" {...props}></Icon>
