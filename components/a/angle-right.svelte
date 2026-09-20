<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olmqvccrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="olmqvccrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:angle-right" {...props}></Icon>
