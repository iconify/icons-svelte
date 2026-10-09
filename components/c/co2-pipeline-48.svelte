<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaq0blbdk.css';
import '../../css/p/ppdr4b5kz.css';
import '../../css/y/y7x0imbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oaq0blbdk"/><path class="ppdr4b5kz"/><path class="y7x0imbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-pipeline-48" {...props}></Icon>
