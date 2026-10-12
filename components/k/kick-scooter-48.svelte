<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amb3slunr.css';
import '../../css/p/prn6stb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="amb3slunr"/><path class="prn6stb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kick-scooter-48" {...props}></Icon>
