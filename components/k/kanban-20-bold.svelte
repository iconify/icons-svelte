<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nivpnqg4j.css';
import '../../css/d/dy4xl-b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nivpnqg4j"/><path class="dy4xl-b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kanban-20-bold" {...props}></Icon>
