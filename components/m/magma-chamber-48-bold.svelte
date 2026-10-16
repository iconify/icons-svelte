<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pivyf-bap.css';
import '../../css/e/eo4t4pbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pivyf-bap"/><path class="eo4t4pbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:magma-chamber-48-bold" {...props}></Icon>
