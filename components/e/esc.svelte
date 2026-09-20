<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc0pt313m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sc0pt313m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:esc" {...props}></Icon>
