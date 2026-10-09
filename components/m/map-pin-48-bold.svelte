<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etlms99xu.css';
import '../../css/a/atnbb5brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="etlms99xu"/><path class="atnbb5brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:map-pin-48-bold" {...props}></Icon>
