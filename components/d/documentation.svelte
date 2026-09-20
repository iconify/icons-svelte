<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al7hf0ijn.css';
import '../../css/p/p5oxreb1k.css';
import '../../css/q/qyivhdcvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="al7hf0ijn"/><path class="p5oxreb1k"/><path class="qyivhdcvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:documentation" {...props}></Icon>
