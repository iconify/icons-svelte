<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klcw8eg5x.css';
import '../../css/s/s55bi35kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="klcw8eg5x"/><path class="s55bi35kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frame-48-bold" {...props}></Icon>
