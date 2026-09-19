<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma3n16bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":1024};
const content = `<path class="ma3n16bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:metronome" {...props}></Icon>
