<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k16ypzb4q.css';
import '../../css/o/o2az-abuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k16ypzb4q"/><path class="o2az-abuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nuclear-plant-48" {...props}></Icon>
