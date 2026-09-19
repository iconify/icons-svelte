<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0cz78sbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r0cz78sbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:ripple" {...props}></Icon>
