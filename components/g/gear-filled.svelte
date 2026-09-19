<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8vb0zkdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l8vb0zkdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:gear-filled" {...props}></Icon>
