<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh930abre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bh930abre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:pause" {...props}></Icon>
