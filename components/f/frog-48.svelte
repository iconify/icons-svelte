<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cifz9-27c.css';
import '../../css/w/w1o4mgb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cifz9-27c"/><path class="w1o4mgb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frog-48" {...props}></Icon>
