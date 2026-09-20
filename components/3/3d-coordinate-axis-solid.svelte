<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8l76c5tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t8l76c5tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:3d-coordinate-axis-solid" {...props}></Icon>
