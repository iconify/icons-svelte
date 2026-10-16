<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twkhdebna.css';
import '../../css/n/n63jug8iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="twkhdebna"/><path class="n63jug8iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-pen-48" {...props}></Icon>
