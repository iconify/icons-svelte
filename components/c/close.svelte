<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chd-g8bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="chd-g8bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:close" {...props}></Icon>
