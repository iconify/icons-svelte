<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3nx36brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r3nx36brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:grid" {...props}></Icon>
