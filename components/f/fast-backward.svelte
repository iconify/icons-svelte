<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqlg3vbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iqlg3vbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:fast-backward" {...props}></Icon>
