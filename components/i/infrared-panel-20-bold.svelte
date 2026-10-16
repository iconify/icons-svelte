<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afx4zacet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="afx4zacet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:infrared-panel-20-bold" {...props}></Icon>
