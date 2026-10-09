<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1329qbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m1329qbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parallelogram-48-bold" {...props}></Icon>
