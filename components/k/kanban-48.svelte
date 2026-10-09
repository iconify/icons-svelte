<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htetqt6dv.css';
import '../../css/y/yw1bixbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="htetqt6dv"/><path class="yw1bixbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kanban-48" {...props}></Icon>
