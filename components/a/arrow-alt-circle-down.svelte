<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i37lj7btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i37lj7btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-alt-circle-down" {...props}></Icon>
