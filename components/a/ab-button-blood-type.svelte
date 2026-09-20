<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxwyqi2jz.css';
import '../../css/i/in5wtwq8h.css';
import '../../css/x/xan4wqb6p.css';
import '../../css/e/e4zfowz9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="fxwyqi2jz"/><path class="in5wtwq8h"/><path class="xan4wqb6p"/><path class="e4zfowz9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ab-button-blood-type" {...props}></Icon>
