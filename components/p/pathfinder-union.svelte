<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyox18xaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gyox18xaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pathfinder-union" {...props}></Icon>
