<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3r18vqzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i3r18vqzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:necktie" {...props}></Icon>
