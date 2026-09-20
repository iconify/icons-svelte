<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyp94ybkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lyp94ybkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:check-circle" {...props}></Icon>
