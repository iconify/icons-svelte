<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m39f0nb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m39f0nb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:play" {...props}></Icon>
