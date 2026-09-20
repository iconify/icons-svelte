<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u72deestk.css';
import '../../css/a/a41-ntbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u72deestk"/><path class="a41-ntbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:hourglass" {...props}></Icon>
