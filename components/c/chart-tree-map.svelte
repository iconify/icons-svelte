<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw2yh03_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw2yh03_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-tree-map" {...props}></Icon>
