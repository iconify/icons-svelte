<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-29u-bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s-29u-bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:esc-a" {...props}></Icon>
