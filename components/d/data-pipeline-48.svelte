<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oovvmabkz.css';
import '../../css/p/plqdzxpyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oovvmabkz"/><path class="plqdzxpyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:data-pipeline-48" {...props}></Icon>
