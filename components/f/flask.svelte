<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/som0vccsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="som0vccsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:flask" {...props}></Icon>
