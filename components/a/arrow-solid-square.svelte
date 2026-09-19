<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e7qalcvkx.css';
import '../../css/m/me_9c89nm.css';
import '../../css/f/fmkrf-bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="e7qalcvkx"/><path clip-rule="evenodd" class="me_9c89nm"/><path class="fmkrf-bca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:arrow-solid-square" {...props}></Icon>
