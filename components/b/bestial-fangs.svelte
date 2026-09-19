<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd_4b-b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dd_4b-b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bestial-fangs" {...props}></Icon>
