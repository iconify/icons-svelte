<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwsfmx54m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xwsfmx54m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chart-line" {...props}></Icon>
