<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi3ws8b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vi3ws8b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-grid-48" {...props}></Icon>
