<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbp3x8bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jbp3x8bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:car-seat" {...props}></Icon>
