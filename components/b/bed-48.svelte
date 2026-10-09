<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftft7buul.css';
import '../../css/o/oanow-b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ftft7buul"/><path class="oanow-b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bed-48" {...props}></Icon>
