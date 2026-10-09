<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omdaj5bmv.css';
import '../../css/r/r0o84rlgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="omdaj5bmv"/><path class="r0o84rlgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:copper-48-bold" {...props}></Icon>
