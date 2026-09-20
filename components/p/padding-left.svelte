<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7ch8sbnj.css';
import '../../css/e/epixueb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q7ch8sbnj"/><path class="epixueb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:padding-left" {...props}></Icon>
