<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af5cyabry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="af5cyabry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mars-stroke-up" {...props}></Icon>
