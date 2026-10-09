<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i700qdb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i700qdb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brackets-48-bold" {...props}></Icon>
