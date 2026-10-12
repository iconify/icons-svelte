<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czkug8blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="czkug8blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-strike-stroke-20" {...props}></Icon>
